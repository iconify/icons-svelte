<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8da38ujk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v8da38ujk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:soundwave-square-filled" {...props}></Icon>
