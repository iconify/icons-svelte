<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3jqfjuwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:system-update-sharp" {...props}></Icon>
<style>
:global(.d3jqfjuwn) {
  fill: currentColor;
  d: path("M12 15.308L15.308 12l-.708-.708l-2.1 2.089V8.692h-1v4.689l-2.1-2.089l-.708.708zM6 22V2h12.077v4.83H19v3.686h-.923V22z");
}

</style>
