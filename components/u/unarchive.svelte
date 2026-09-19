<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-f-t6bzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p-f-t6bzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:unarchive" {...props}></Icon>
