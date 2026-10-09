<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3svyccwt.css';
import '../../css/u/us2y8_bfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k3svyccwt"/><path class="us2y8_bfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:spatula-48-bold" {...props}></Icon>
