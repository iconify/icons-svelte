<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye8mq4bhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ye8mq4bhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:sort-ascending-fill-round" {...props}></Icon>
