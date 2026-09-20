<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elsm6go3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="elsm6go3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:webflow" {...props}></Icon>
