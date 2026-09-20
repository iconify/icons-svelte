<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljawfdcha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljawfdcha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:scale-solid" {...props}></Icon>
