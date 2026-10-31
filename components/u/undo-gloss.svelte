<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/heq9tpbdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="heq9tpbdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:undo-gloss" {...props}></Icon>
