<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwj0gbbsy.css';
import '../../css/e/euo04dbov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwj0gbbsy"/><path class="euo04dbov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:sign-out" {...props}></Icon>
