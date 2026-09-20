<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8p0ejb9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v8p0ejb9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:sign-out" {...props}></Icon>
