<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as61apdla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="as61apdla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:thumbs-up" {...props}></Icon>
