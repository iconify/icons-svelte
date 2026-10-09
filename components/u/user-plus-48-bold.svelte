<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhffk1rfs.css';
import '../../css/w/wd6p9pbhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jhffk1rfs"/><path class="wd6p9pbhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-plus-48-bold" {...props}></Icon>
