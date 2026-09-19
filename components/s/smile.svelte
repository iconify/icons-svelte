<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g76107emo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g76107emo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:smile" {...props}></Icon>
