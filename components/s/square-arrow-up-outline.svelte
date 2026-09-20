<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwlve3bru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iwlve3bru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-arrow-up-outline" {...props}></Icon>
