<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3b3ih1nk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a3b3ih1nk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:second-bracket" {...props}></Icon>
