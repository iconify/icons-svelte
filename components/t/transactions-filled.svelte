<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7035obpy.css';
import '../../css/o/oxij2syau.css';
import '../../css/i/izyyfg2ul.css';
import '../../css/n/nqndbxxtm.css';
import '../../css/d/dv_-0ibig.css';
import '../../css/v/vx2gl0tzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="g7035obpy"/><path clip-rule="evenodd" class="oxij2syau"/><circle class="izyyfg2ul"/><path clip-rule="evenodd" class="nqndbxxtm"/><circle class="dv_-0ibig"/><path clip-rule="evenodd" class="vx2gl0tzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:transactions-filled" {...props}></Icon>
