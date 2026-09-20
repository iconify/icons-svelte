<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc-fypaai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jc-fypaai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:wikimediacommons" {...props}></Icon>
