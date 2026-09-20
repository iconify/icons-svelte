<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvyskiz7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dvyskiz7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:traffic-light-solid" {...props}></Icon>
