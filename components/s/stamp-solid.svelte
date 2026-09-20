<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9hqqbcxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a9hqqbcxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:stamp-solid" {...props}></Icon>
