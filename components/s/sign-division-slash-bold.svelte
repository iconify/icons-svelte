<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twqiick_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="twqiick_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-division-slash-bold" {...props}></Icon>
