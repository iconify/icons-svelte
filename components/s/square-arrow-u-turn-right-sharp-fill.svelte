<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbgi3dknm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sbgi3dknm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-arrow-u-turn-right-sharp-fill" {...props}></Icon>
