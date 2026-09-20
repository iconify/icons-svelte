<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1vpt6b7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1vpt6b7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:the-planetary-society" {...props}></Icon>
