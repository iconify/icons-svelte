<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkh8yvkml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lkh8yvkml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:user-minus-filled" {...props}></Icon>
