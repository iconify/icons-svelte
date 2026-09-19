<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iun5hukdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1280,"height":1472};
const content = `<path class="iun5hukdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:user-suit-female" {...props}></Icon>
