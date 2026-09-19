<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/b/bu-u2ebah.css';
import '../../css/h/hlrq6c2ew.css';
import '../../css/f/fb921obvg.css';
import '../../css/f/fh4k-wbtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="bu-u2ebah"/><path class="hlrq6c2ew"/><path class="fb921obvg"/><path class="fh4k-wbtv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:test-tube" {...props}></Icon>
