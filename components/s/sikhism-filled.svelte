<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlninacrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zlninacrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sikhism-filled" {...props}></Icon>
