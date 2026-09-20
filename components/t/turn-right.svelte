<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/h/hg47tl.css';
import '../../css/b/blypte.css';
import '../../css/s/so-from-24.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c hg47tl"/><path class="a0m25c blypte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:turn-right" {...props}></Icon>
