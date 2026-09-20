<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kji3f8xww.css';
import '../../css/m/m0_ghw2pl.css';
import '../../css/i/ietn-5oir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kji3f8xww"/><circle class="m0_ghw2pl"/><path class="ietn-5oir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:systemd-light" {...props}></Icon>
