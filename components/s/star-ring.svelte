<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b65-p4bii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b65-p4bii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:star-ring" {...props}></Icon>
