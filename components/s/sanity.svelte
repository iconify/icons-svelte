<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-5ogob0g.css';
import '../../css/i/il_nhwj0r.css';
import '../../css/d/dh0pfppzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="q-5ogob0g"/><path class="il_nhwj0r"/><path class="dh0pfppzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:sanity" {...props}></Icon>
