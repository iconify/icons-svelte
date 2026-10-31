<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kez3htb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="kez3htb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="struq:step-todo" {...props}></Icon>
