<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8dbiybih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c8dbiybih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:share-nodes-outline" {...props}></Icon>
