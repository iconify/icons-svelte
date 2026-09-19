<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwy6e0b_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mwy6e0b_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:rows-two-alt" {...props}></Icon>
