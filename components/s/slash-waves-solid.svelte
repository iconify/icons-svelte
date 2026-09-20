<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmk8c0bnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jmk8c0bnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:slash-waves-solid" {...props}></Icon>
