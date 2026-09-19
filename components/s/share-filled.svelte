<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjvpjubyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjvpjubyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:share-filled" {...props}></Icon>
