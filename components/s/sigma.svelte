<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7wtvsbvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y7wtvsbvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:sigma" {...props}></Icon>
