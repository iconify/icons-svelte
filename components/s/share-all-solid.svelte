<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owku4lbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="owku4lbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:share-all-solid" {...props}></Icon>
