<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy6ocrb8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yy6ocrb8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:user-feedback-heart-remix" {...props}></Icon>
