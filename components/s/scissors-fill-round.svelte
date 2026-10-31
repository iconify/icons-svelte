<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5ovq8b1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5ovq8b1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:scissors-fill-round" {...props}></Icon>
