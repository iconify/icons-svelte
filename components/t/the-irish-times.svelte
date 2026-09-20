<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grkmx94ls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grkmx94ls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:the-irish-times" {...props}></Icon>
