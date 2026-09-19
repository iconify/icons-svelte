<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlpmq0bce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlpmq0bce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:tree-alt-filled" {...props}></Icon>
