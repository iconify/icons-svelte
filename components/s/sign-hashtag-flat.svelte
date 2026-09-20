<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afr4k7jkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="afr4k7jkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:sign-hashtag-flat" {...props}></Icon>
