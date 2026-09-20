<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6hedybii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m6hedybii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:smile-square-filled" {...props}></Icon>
