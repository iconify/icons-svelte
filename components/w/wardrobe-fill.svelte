<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jujyugb5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jujyugb5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wardrobe-fill" {...props}></Icon>
