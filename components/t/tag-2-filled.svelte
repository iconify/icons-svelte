<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdspn4blu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mdspn4blu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:tag-2-filled" {...props}></Icon>
