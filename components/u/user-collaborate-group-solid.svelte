<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so2n3wg9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="so2n3wg9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:user-collaborate-group-solid" {...props}></Icon>
