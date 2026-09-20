<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0jw8gyfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-2};
const content = `<path class="m0jw8gyfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:speaker" {...props}></Icon>
