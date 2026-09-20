<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/buki-ebqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="buki-ebqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:textalign-center-filled" {...props}></Icon>
