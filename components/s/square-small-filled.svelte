<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgy0d7bqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="wgy0d7bqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:square-small-filled" {...props}></Icon>
