<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsekujfii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jsekujfii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:zoom" {...props}></Icon>
