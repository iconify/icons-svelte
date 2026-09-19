<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1a0p5jnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="l1a0p5jnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:thermometer" {...props}></Icon>
