<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3rwybcyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v3rwybcyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:trash-alt-filled" {...props}></Icon>
