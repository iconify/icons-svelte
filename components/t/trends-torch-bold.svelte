<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfenr6sbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfenr6sbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:trends-torch-bold" {...props}></Icon>
