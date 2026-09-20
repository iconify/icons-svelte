<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhyjz8bkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bhyjz8bkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:video-fill" {...props}></Icon>
