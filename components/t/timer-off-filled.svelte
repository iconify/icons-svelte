<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqgrt7b6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dqgrt7b6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:timer-off-filled" {...props}></Icon>
