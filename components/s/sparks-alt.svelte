<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz3basbvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vz3basbvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:sparks-alt" {...props}></Icon>
