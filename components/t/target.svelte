<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/s/ssxi8fbrc.css';
import '../../css/q/qzi6x3eeu.css';
import '../../css/b/bqwt9iilj.css';
import '../../css/f/ftvkakb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="ssxi8fbrc wm-shadow"/><path class="qzi6x3eeu wm-shadow"/><path class="bqwt9iilj"/><path class="ftvkakb5w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:target" {...props}></Icon>
