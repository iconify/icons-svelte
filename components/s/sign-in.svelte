<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apiedpb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1280};
const content = `<path class="apiedpb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:sign-in" {...props}></Icon>
