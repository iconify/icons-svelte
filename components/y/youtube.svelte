<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edziozbwe.css';
import '../../css/x/xiw15t9pv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="edziozbwe"/><path class="xiw15t9pv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:youtube" {...props}></Icon>
