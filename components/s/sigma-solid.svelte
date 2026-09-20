<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v03-aihml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v03-aihml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:sigma-solid" {...props}></Icon>
