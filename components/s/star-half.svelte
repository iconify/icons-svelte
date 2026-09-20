<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofnqb8bqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ofnqb8bqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:star-half" {...props}></Icon>
