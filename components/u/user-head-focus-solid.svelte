<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0rpwupio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l0rpwupio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:user-head-focus-solid" {...props}></Icon>
