<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1uqu1b1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1uqu1b1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:undo-outline" {...props}></Icon>
