<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp02o6b7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hp02o6b7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:send" {...props}></Icon>
