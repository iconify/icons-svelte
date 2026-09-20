<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl6wsu4jo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zl6wsu4jo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:tablet-filled" {...props}></Icon>
