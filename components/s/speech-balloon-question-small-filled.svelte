<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ube0iz5zh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ube0iz5zh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:speech-balloon-question-small-filled" {...props}></Icon>
