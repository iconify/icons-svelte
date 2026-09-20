<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3qeq8b8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j3qeq8b8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:tea-cup-filled" {...props}></Icon>
