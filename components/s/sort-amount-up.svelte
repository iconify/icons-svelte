<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7sy1g2se.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="o7sy1g2se"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:sort-amount-up" {...props}></Icon>
