<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odslhv3ql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="odslhv3ql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:share-05" {...props}></Icon>
