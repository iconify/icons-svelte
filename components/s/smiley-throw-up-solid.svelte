<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbcwptdbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bbcwptdbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:smiley-throw-up-solid" {...props}></Icon>
