<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7sd8bcqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d7sd8bcqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:share-2-fill" {...props}></Icon>
