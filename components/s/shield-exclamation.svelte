<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-kl0888x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-kl0888x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:shield-exclamation" {...props}></Icon>
