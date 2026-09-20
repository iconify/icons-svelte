<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scz9fkbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scz9fkbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:venmo" {...props}></Icon>
