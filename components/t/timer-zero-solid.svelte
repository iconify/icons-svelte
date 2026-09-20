<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kl99exb8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kl99exb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:timer-zero-solid" {...props}></Icon>
