<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iybzt3kih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="iybzt3kih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:share-from-square" {...props}></Icon>
