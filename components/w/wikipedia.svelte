<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae21gbbfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ae21gbbfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:wikipedia" {...props}></Icon>
