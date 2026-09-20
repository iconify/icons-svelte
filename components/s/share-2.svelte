<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6c3cv0ul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6c3cv0ul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:share-2" {...props}></Icon>
