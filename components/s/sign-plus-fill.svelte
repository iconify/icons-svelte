<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0m7wi98f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h0m7wi98f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-plus-fill" {...props}></Icon>
