<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxq6v60ur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bxq6v60ur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sim" {...props}></Icon>
