<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yag1ve2fw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yag1ve2fw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:store" {...props}></Icon>
