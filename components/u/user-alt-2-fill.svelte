<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtlo8iikr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gtlo8iikr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:user-alt-2-fill" {...props}></Icon>
