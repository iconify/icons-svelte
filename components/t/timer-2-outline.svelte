<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nz41hjbhh.css';
import '../../css/o/os6iakbao.css';
import '../../css/m/mces9ir0s.css';
import '../../css/q/qaew_5b7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="nz41hjbhh"/><path class="os6iakbao"/><path class="mces9ir0s"/><path class="qaew_5b7f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:timer-2-outline" {...props}></Icon>
