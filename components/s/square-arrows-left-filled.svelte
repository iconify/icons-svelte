<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp7m51byk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dp7m51byk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:square-arrows-left-filled" {...props}></Icon>
