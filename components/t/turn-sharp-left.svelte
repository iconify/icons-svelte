<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/c/ct9-oq.css';
import '../../css/j/jzrh9t.css';
import '../../css/s/so-from-28.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c ct9-oq"/><path class="a0m25c jzrh9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:turn-sharp-left" {...props}></Icon>
