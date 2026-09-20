<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu-junbcx.css';
import '../../css/j/jicrk8bfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nu-junbcx"/><path clip-rule="evenodd" class="jicrk8bfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:trash-24" {...props}></Icon>
