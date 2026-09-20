<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4etpy67f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4etpy67f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:soundcloud" {...props}></Icon>
