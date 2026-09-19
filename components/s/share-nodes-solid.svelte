<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq34xdb4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fq34xdb4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:share-nodes-solid" {...props}></Icon>
