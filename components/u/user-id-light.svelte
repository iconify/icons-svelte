<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/payoqhbax.css';
import '../../css/f/fnuy0_9ha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="payoqhbax"/><path class="fnuy0_9ha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:user-id-light" {...props}></Icon>
