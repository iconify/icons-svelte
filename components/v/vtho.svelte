<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gw7nf2z4x.css';
import '../../css/m/md286fbip.css';
import '../../css/b/bbtysibbk.css';
import '../../css/e/eu27vsb0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="gw7nf2z4x"/><g class="md286fbip"><path class="bbtysibbk"/><path class="eu27vsb0f"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:vtho" {...props}></Icon>
