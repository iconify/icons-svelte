<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q680kxb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="q680kxb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:store-alt" {...props}></Icon>
