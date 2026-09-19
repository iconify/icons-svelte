<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3v73bb-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a3v73bb-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:umbrella" {...props}></Icon>
