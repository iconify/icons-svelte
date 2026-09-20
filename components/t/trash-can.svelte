<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n923nubfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n923nubfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:trash-can" {...props}></Icon>
