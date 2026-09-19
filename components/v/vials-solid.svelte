<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te7bb6ppf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="te7bb6ppf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:vials-solid" {...props}></Icon>
