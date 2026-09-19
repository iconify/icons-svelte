<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0bk0ccsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g0bk0ccsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:skype" {...props}></Icon>
