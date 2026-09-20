<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/g/gnjcyx.css';
import '../../css/o/oiu1id.css';
import '../../css/s/so-from-20.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c gnjcyx"/><path class="a0m25c oiu1id"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:turn-slight-right" {...props}></Icon>
