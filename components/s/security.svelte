<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsrsxu2on.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gsrsxu2on"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:security" {...props}></Icon>
