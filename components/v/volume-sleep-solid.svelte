<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hulypnb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hulypnb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:volume-sleep-solid" {...props}></Icon>
