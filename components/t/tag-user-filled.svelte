<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8gmagbkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8gmagbkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:tag-user-filled" {...props}></Icon>
