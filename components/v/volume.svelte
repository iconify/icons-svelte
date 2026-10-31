<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/a/akp692bkr.css';
import '../../css/g/gic9po5yn.css';
import '../../css/h/hhwgsyjct.css';
import '../../css/f/fquzhwn-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="akp692bkr wm-shadow"/><path class="gic9po5yn wm-shadow"/><path class="hhwgsyjct"/><path class="fquzhwn-n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:volume" {...props}></Icon>
