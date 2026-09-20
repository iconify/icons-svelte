<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myf97jsmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="myf97jsmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:rubel-circle" {...props}></Icon>
