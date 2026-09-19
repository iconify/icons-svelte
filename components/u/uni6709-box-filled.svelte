<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4al-jb7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="k4al-jb7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:uni6709-box-filled" {...props}></Icon>
