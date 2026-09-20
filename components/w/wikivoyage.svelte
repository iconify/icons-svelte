<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1k5pbbfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v1k5pbbfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:wikivoyage" {...props}></Icon>
