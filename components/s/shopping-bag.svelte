<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqx37mbba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="uqx37mbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:shopping-bag" {...props}></Icon>
