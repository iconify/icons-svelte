<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymluktg6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ymluktg6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:user-multiple-02" {...props}></Icon>
