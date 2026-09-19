<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvbqoqldh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hvbqoqldh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:speaker-x-mark" {...props}></Icon>
