<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgg4dq8pa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tgg4dq8pa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:users-nearby" {...props}></Icon>
