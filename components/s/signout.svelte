<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m11n33b9i.css';
import '../../css/x/xt5xc0eya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m11n33b9i"/><path class="xt5xc0eya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:signout" {...props}></Icon>
