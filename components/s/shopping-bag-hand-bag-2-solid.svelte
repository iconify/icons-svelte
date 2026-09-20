<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4kl6cbwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l4kl6cbwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shopping-bag-hand-bag-2-solid" {...props}></Icon>
