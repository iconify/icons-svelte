<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czi0srbta.css';
import '../../css/c/cdpzc0bqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="czi0srbta"/><path class="cdpzc0bqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:users-crown" {...props}></Icon>
