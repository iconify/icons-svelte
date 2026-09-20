<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du6iv0jkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="du6iv0jkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:triangle-warning-filled" {...props}></Icon>
